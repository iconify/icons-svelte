<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak8bbzg-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ak8bbzg-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:house-door" {...props}></Icon>
