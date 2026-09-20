<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8hsgjgyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8hsgjgyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:flip-horizontal-2" {...props}></Icon>
