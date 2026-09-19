<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il88ib7ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="il88ib7ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:caret-left-fill" {...props}></Icon>
