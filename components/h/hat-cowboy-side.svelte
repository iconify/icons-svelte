<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsams5bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="zsams5bxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hat-cowboy-side" {...props}></Icon>
