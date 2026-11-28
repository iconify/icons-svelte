<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6ehqfbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6ehqfbqs primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:check-duotone" {...props}></Icon>
