<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jolpr0egc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jolpr0egc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:parking-meter-solid" {...props}></Icon>
