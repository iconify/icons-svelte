<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_l8s7bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t_l8s7bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-square-vert-fill" {...props}></Icon>
