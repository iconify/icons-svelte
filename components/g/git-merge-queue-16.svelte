<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_ve0iaje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y_ve0iaje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-merge-queue-16" {...props}></Icon>
