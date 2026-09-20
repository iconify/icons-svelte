<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/o/o3rybj.css';
import '../../css/j/j8ttiv.css';
import '../../css/s/so-from-18.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c o3rybj"/><path class="a0m25c j8ttiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:round-ramp-left" {...props}></Icon>
