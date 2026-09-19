<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf5_zmbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uf5_zmbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cloud-off-filled" {...props}></Icon>
