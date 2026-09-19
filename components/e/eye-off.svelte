<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7slzmblf.css';
import '../../css/y/ywurx5bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q7slzmblf"/><path class="ywurx5bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:eye-off" {...props}></Icon>
