<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qab_zlbij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qab_zlbij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:diamond-gem" {...props}></Icon>
