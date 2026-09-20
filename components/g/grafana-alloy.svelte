<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpoyy9bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpoyy9bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:grafana-alloy" {...props}></Icon>
