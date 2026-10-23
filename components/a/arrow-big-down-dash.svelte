<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prkoaib7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prkoaib7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-big-down-dash" {...props}></Icon>
