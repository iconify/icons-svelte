<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlwb9e1jw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mlwb9e1jw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-added-16" {...props}></Icon>
