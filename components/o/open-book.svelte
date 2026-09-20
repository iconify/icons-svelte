<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndf6uogjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ndf6uogjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:open-book" {...props}></Icon>
