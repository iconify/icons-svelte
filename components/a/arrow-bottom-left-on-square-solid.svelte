<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wycc4kp6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wycc4kp6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-bottom-left-on-square-solid" {...props}></Icon>
