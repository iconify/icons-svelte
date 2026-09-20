<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il8wh0bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="il8wh0bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:archive" {...props}></Icon>
