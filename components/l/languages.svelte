<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_q_2eb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_q_2eb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:languages" {...props}></Icon>
