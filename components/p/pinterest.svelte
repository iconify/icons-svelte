<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgo7glb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgo7glb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:pinterest" {...props}></Icon>
