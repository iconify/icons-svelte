<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkym8bcai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkym8bcai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:angles-left" {...props}></Icon>
