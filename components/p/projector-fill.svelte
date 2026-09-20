<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmj5--bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmj5--bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:projector-fill" {...props}></Icon>
