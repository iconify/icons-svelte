<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ianouabio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ianouabio primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:git-fork-duotone" {...props}></Icon>
