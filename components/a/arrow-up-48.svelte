<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df1n7oboy.css';
import '../../css/z/z6uccbt4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="df1n7oboy"/><path class="z6uccbt4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-48" {...props}></Icon>
