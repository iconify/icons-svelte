<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqp16abjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nqp16abjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:key" {...props}></Icon>
