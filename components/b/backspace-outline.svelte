<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxx9vvbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxx9vvbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:backspace-outline" {...props}></Icon>
