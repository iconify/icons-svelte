<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u393f9bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u393f9bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:face-wink-filled" {...props}></Icon>
