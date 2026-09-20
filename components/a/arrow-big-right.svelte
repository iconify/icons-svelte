<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfdad1bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfdad1bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-big-right" {...props}></Icon>
