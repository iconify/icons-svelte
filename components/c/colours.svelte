<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-h2w1yfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q-h2w1yfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:colours" {...props}></Icon>
