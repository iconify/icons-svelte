<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh7v1eb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qh7v1eb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:play-box-lock-outline" {...props}></Icon>
