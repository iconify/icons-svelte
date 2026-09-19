<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfqn_kb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kfqn_kb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:centos" {...props}></Icon>
