<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnyr7tqvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnyr7tqvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dislike-fill" {...props}></Icon>
