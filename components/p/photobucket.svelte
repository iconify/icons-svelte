<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4tf0bwnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="p4tf0bwnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:photobucket" {...props}></Icon>
