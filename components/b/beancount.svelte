<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfhdwq6la.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pfhdwq6la"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:beancount" {...props}></Icon>
