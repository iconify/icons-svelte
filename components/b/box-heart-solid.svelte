<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h48g7vb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h48g7vb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:box-heart-solid" {...props}></Icon>
