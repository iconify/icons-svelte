<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq43k1bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qq43k1bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:army-tent" {...props}></Icon>
