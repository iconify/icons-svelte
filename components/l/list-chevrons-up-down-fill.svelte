<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrre46b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrre46b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-chevrons-up-down-fill" {...props}></Icon>
