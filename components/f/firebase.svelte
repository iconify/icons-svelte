<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra33s9tks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra33s9tks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:firebase" {...props}></Icon>
