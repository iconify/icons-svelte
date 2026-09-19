<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf__9iawb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vf__9iawb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:grafana-wordmark" {...props}></Icon>
