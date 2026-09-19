<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae5cuqhku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ae5cuqhku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:arrow-long-down" {...props}></Icon>
