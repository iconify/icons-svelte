<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auabr42fn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auabr42fn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:code-light" {...props}></Icon>
