<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miy_jjbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":32};
const content = `<path class="miy_jjbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:lightbulb" {...props}></Icon>
