<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wckr9kb1z.css';
import '../../css/j/jzowd3bfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wckr9kb1z"/><path class="jzowd3bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:plus-circle-outline" {...props}></Icon>
