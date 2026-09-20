<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbv__ub4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zbv__ub4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:dribbble-logo-solid" {...props}></Icon>
