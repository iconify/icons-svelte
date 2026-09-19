<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl8zml4wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl8zml4wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:app-menu" {...props}></Icon>
