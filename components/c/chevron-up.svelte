<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig5d7vufz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ig5d7vufz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-up" {...props}></Icon>
