<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uikk2ibkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uikk2ibkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:building" {...props}></Icon>
