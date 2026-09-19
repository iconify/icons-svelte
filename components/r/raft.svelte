<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmq8exbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hmq8exbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:raft" {...props}></Icon>
