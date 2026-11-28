<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akaspub_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akaspub_j primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:parenthesis-right-duotone" {...props}></Icon>
