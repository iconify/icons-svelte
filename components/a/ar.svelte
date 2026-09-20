<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt7khlbia.css';
import '../../css/i/ib0lxob6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt7khlbia"/><path class="ib0lxob6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ar" {...props}></Icon>
