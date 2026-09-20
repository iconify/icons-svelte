<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpgjb18la.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpgjb18la"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:nuxt" {...props}></Icon>
