<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo1ogpb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qo1ogpb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bix" {...props}></Icon>
