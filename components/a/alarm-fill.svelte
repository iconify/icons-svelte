<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp2zgn6iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pp2zgn6iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:alarm-fill" {...props}></Icon>
