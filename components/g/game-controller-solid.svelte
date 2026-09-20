<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_fd73x_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="t_fd73x_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:game-controller-solid" {...props}></Icon>
