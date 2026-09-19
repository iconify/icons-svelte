<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gicopp7ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gicopp7ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:club-suit" {...props}></Icon>
