<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sro0m4o8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sro0m4o8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:lemonsqueezy-filled" {...props}></Icon>
