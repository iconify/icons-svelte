<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj6mqtbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cj6mqtbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:envelope-unread" {...props}></Icon>
