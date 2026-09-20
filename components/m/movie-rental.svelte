<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6m6xlb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="q6m6xlb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:movie-rental" {...props}></Icon>
