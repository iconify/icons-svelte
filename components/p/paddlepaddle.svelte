<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj0pjvbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zj0pjvbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:paddlepaddle" {...props}></Icon>
