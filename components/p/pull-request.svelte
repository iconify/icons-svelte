<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abgdj92nu.css';
import '../../css/g/ggga5ib7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="abgdj92nu"/><path class="ggga5ib7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:pull-request" {...props}></Icon>
