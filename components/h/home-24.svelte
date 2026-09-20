<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efeintbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efeintbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:home-24" {...props}></Icon>
