<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3pkaci9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="u3pkaci9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:align-center" {...props}></Icon>
