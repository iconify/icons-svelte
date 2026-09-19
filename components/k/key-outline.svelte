<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb59htb_d.css';
import '../../css/k/k4or6zb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb59htb_d"/><path clip-rule="evenodd" class="k4or6zb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:key-outline" {...props}></Icon>
