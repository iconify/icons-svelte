<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqc0zky1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kqc0zky1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:control-end" {...props}></Icon>
