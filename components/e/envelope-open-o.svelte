<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzzp38b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fzzp38b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:envelope-open-o" {...props}></Icon>
