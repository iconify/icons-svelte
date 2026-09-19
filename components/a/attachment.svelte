<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksvj0z6ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="ksvj0z6ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:attachment" {...props}></Icon>
