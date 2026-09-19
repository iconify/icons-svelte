<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gprqh4byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gprqh4byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-x" {...props}></Icon>
