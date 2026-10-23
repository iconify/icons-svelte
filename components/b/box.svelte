<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmenw7bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmenw7bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:box" {...props}></Icon>
