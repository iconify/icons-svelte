<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjrh5hfer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjrh5hfer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-left" {...props}></Icon>
