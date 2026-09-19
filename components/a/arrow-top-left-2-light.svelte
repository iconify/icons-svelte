<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guektbcso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="guektbcso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-left-2-light" {...props}></Icon>
