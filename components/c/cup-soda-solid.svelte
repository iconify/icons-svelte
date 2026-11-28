<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax6l9-l3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax6l9-l3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cup-soda-solid" {...props}></Icon>
