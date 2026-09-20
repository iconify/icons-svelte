<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b16pw7s_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b16pw7s_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coughing-face-in-circle-outline" {...props}></Icon>
