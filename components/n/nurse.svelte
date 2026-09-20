<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7z45hb6b.css';
import '../../css/s/s7g2vkbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v7z45hb6b"/><path class="s7g2vkbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:nurse" {...props}></Icon>
