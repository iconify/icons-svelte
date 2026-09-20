<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecc9xbbqc.css';
import '../../css/m/mmxphf4-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecc9xbbqc"/><path clip-rule="evenodd" class="mmxphf4-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:haze-fill" {...props}></Icon>
