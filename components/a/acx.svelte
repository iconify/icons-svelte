<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udn5eiblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udn5eiblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:acx" {...props}></Icon>
