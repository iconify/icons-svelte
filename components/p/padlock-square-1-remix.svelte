<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_tevem9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q_tevem9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:padlock-square-1-remix" {...props}></Icon>
