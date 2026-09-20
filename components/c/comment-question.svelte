<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riyd5ab2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="riyd5ab2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-question" {...props}></Icon>
