<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f87a287-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="f87a287-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:hamburger-small" {...props}></Icon>
