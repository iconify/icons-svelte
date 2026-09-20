<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9hlq-bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9hlq-bmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:border-left" {...props}></Icon>
