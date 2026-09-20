<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lccrvp42b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lccrvp42b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:badge-account-alert-outline" {...props}></Icon>
