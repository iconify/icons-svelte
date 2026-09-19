<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jux9gab8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":448};
const content = `<path class="jux9gab8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:eye" {...props}></Icon>
