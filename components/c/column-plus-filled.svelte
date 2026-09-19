<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdym82bfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdym82bfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:column-plus-filled" {...props}></Icon>
