<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-my5lk7s.css';
import '../../css/g/g8crnxb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o-my5lk7s"/><path class="g8crnxb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:accessibility" {...props}></Icon>
