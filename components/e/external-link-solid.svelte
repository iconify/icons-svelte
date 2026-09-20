<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy7q00b8z.css';
import '../../css/l/lbxyuzatw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cy7q00b8z"/><path class="lbxyuzatw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:external-link-solid" {...props}></Icon>
