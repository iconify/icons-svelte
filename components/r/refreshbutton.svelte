<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_pzzib7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":717};
const content = `<path class="q_pzzib7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:refreshbutton" {...props}></Icon>
