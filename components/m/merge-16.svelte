<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebo_mom1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ebo_mom1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:merge-16" {...props}></Icon>
