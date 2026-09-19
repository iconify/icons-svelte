<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h84l40bgj.css';
import '../../css/w/wckr9kb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h84l40bgj"/><path class="wckr9kb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrow-circle-left-outline" {...props}></Icon>
