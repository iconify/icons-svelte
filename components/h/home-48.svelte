<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xypximg7a.css';
import '../../css/b/bqvhui-iq.css';
import '../../css/k/k167alb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xypximg7a"/><path class="bqvhui-iq"/><path class="k167alb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:home-48" {...props}></Icon>
