<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdhdh5hpt.css';
import '../../css/k/keuh4feao.css';
import '../../css/h/hu_cubcac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdhdh5hpt"/><path class="keuh4feao"/><path class="hu_cubcac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:hourglass" {...props}></Icon>
