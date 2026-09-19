<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7d34xbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7d34xbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:halloween-tomb-filled" {...props}></Icon>
