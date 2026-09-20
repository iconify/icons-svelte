<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3hg3vhxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3hg3vhxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rollercoaster-filled" {...props}></Icon>
