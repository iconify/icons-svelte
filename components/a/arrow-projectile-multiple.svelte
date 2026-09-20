<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjk-7-7jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjk-7-7jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-projectile-multiple" {...props}></Icon>
