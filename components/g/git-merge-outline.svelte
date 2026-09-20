<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih8imdosu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ih8imdosu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:git-merge-outline" {...props}></Icon>
