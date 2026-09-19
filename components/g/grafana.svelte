<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2_1oxfmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2_1oxfmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:grafana" {...props}></Icon>
