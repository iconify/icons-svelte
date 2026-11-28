<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jglj7vlwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jglj7vlwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-up-solid" {...props}></Icon>
