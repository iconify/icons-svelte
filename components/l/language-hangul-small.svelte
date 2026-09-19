<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpeg90bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vpeg90bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-hangul-small" {...props}></Icon>
