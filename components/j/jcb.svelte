<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqarkh7mf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqarkh7mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:jcb" {...props}></Icon>
