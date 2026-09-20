<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkqtxxnbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkqtxxnbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-user-outline" {...props}></Icon>
