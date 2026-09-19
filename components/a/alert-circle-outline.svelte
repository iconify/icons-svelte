<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wckr9kb1z.css';
import '../../css/i/iu35e1xme.css';
import '../../css/x/xjqcgab4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wckr9kb1z"/><circle class="iu35e1xme"/><path class="xjqcgab4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:alert-circle-outline" {...props}></Icon>
