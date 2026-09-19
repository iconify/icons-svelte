<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsmsgs7un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dsmsgs7un"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:mnx" {...props}></Icon>
