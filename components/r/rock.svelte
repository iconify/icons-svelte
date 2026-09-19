<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggo69_jeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ggo69_jeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:rock" {...props}></Icon>
