<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvvf-pbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yvvf-pbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:meditation-round-outline" {...props}></Icon>
