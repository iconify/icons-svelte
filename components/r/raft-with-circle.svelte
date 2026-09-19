<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb4b0hbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lb4b0hbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:raft-with-circle" {...props}></Icon>
