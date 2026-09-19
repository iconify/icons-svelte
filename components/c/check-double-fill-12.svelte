<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of6vnd3yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="of6vnd3yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-double-fill-12" {...props}></Icon>
