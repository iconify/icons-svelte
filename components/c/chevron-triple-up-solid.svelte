<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oylaiyb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oylaiyb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-triple-up-solid" {...props}></Icon>
