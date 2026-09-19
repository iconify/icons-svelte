<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/m/mdv0qppql.css';
import '../../css/v/vpp8cv3zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="mdv0qppql"/><path class="vpp8cv3zx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:apigee-api-platform" {...props}></Icon>
