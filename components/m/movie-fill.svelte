<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvua4obxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvua4obxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:movie-fill" {...props}></Icon>
