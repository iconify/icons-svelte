<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldn6wy7kf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldn6wy7kf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:minimize-alt" {...props}></Icon>
