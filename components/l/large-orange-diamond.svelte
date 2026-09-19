<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an3el_c8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="an3el_c8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:large-orange-diamond" {...props}></Icon>
