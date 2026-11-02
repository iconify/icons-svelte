<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojitldbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojitldbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:projector-screen-fill" {...props}></Icon>
