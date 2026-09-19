<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m769hdc0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m769hdc0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-x-fill" {...props}></Icon>
