<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuvrm472q.css';
import '../../css/n/nzmy_41cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yuvrm472q"/><path class="nzmy_41cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-turbine-20-bold" {...props}></Icon>
