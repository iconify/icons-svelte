<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayia89h2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ayia89h2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:circle-4" {...props}></Icon>
