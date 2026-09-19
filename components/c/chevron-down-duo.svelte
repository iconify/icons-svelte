<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9vamwuzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9vamwuzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chevron-down-duo" {...props}></Icon>
