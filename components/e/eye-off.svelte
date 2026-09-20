<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiu-54b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hiu-54b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:eye-off" {...props}></Icon>
