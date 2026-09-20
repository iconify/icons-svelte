<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa3ll2bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa3ll2bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:kfc" {...props}></Icon>
