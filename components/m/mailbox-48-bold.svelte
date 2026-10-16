<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvfjtltty.css';
import '../../css/l/livgcivqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hvfjtltty"/><path class="livgcivqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mailbox-48-bold" {...props}></Icon>
