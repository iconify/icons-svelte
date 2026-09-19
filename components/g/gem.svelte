<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzy02n6it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzy02n6it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gem" {...props}></Icon>
