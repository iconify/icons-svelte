<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlwnb5eal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlwnb5eal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-down01" {...props}></Icon>
