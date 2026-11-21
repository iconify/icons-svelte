<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj1o8w1sa.css';
import '../../css/i/idl12ys4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj1o8w1sa"/><path class="idl12ys4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-rain-filled" {...props}></Icon>
