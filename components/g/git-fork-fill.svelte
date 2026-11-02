<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygpz85bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygpz85bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-fork-fill" {...props}></Icon>
