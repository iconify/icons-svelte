<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnwu_acdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnwu_acdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:pen-fill" {...props}></Icon>
