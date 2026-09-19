<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f85ruzeha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f85ruzeha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:home-01" {...props}></Icon>
