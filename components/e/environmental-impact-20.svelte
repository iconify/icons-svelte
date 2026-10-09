<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bodkpqb0q.css';
import '../../css/a/a07z9hbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bodkpqb0q"/><path class="a07z9hbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:environmental-impact-20" {...props}></Icon>
