<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf6cugnxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cf6cugnxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:buttony" {...props}></Icon>
