<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs_o25eyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1024};
const content = `<path class="vs_o25eyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:flaskfull" {...props}></Icon>
