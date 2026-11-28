<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldwjd48ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldwjd48ex primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevrons-left-right-duotone" {...props}></Icon>
