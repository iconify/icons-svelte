<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl26tzb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vl26tzb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-cross-outline" {...props}></Icon>
