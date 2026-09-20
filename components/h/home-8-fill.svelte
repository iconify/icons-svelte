<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jor5hct3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jor5hct3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-8-fill" {...props}></Icon>
