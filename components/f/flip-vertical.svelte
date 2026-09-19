<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb-69sr1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rb-69sr1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:flip-vertical" {...props}></Icon>
