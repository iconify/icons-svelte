<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqh7-ab3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":18};
const content = `<path class="bqh7-ab3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:meson" {...props}></Icon>
