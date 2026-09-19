<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwvs0hbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="bwvs0hbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:document" {...props}></Icon>
