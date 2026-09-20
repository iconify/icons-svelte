<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxhe1qt7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mxhe1qt7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:github-fill-16" {...props}></Icon>
