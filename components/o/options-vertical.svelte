<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0-gr6bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q0-gr6bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:options-vertical" {...props}></Icon>
