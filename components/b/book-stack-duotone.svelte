<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc3st3bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fc3st3bkj primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:book-stack-duotone" {...props}></Icon>
