<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp60qnapt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":303,"height":303};
const content = `<path class="sp60qnapt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apollodotio" {...props}></Icon>
