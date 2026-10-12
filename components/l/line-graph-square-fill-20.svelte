<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grb5_qoaa.css';
import '../../css/p/pwjqkc8pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="grb5_qoaa"/><path class="pwjqkc8pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:line-graph-square-fill-20" {...props}></Icon>
