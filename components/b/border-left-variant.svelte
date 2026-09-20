<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aro9nj3gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aro9nj3gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:border-left-variant" {...props}></Icon>
