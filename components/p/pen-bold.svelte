<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t66hbfb2l.css';
import '../../css/b/bkakk0bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t66hbfb2l"/><path class="bkakk0bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pen-bold" {...props}></Icon>
