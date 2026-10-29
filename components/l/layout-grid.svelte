<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-877v1pe.css';
import '../../css/e/e-_uqrb9d.css';
import '../../css/i/ijz6zybvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-877v1pe"/><path class="e-_uqrb9d"/><path class="ijz6zybvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:layout-grid" {...props}></Icon>
