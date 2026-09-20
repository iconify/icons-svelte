<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyjxv0bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eyjxv0bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:banjo-16" {...props}></Icon>
