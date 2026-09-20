<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c07avib5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c07avib5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pendulum" {...props}></Icon>
