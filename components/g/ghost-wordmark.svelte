<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txt8bqbzk.css';
import '../../css/d/dbsyz0f1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="txt8bqbzk"/><path class="dbsyz0f1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ghost-wordmark" {...props}></Icon>
