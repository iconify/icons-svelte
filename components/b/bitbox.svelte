<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5g7eibdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5g7eibdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bitbox" {...props}></Icon>
