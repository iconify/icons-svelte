<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd67zp7vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd67zp7vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:computer-fill" {...props}></Icon>
