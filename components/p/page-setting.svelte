<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_e3mtb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="y_e3mtb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:page-setting" {...props}></Icon>
