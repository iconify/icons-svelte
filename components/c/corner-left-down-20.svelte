<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shss9gboo.css';
import '../../css/w/wik2ozbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="shss9gboo"/><path class="wik2ozbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-left-down-20" {...props}></Icon>
