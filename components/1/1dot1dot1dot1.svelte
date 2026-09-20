<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyoppmmkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyoppmmkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:1dot1dot1dot1" {...props}></Icon>
