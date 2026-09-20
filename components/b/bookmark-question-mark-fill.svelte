<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn6ghm8vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn6ghm8vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:bookmark-question-mark-fill" {...props}></Icon>
