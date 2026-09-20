<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_u9_2ywp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u_u9_2ywp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:box-outline" {...props}></Icon>
