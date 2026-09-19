<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgphr9pxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<ellipse class="xgphr9pxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:oval" {...props}></Icon>
