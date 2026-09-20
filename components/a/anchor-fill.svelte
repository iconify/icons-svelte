<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cje30fbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cje30fbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:anchor-fill" {...props}></Icon>
