<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb5w26egd.css';
import '../../css/k/khx4kzbyh.css';
import '../../css/b/bk45kcouj.css';
import '../../css/u/ua5929fxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yb5w26egd"/><path class="khx4kzbyh"/><path class="bk45kcouj"/><path class="ua5929fxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-expand" {...props}></Icon>
