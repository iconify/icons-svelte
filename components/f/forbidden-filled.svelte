<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-9kcvbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-9kcvbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:forbidden-filled" {...props}></Icon>
