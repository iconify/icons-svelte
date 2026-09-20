<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxc60ek4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxc60ek4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-refresh-sharp" {...props}></Icon>
