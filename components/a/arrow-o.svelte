<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac7gi5bnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ac7gi5bnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:arrow-o" {...props}></Icon>
