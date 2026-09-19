<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8htchb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8htchb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:note" {...props}></Icon>
