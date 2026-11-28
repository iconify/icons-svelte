<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu-hd0b9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bu-hd0b9t primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:command-duotone" {...props}></Icon>
