<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6moad0xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="p6moad0xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:closed-book-filled" {...props}></Icon>
