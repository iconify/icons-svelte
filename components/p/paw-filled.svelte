<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8e9zabhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8e9zabhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:paw-filled" {...props}></Icon>
