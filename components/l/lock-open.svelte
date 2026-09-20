<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b03t9pb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b03t9pb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:lock-open" {...props}></Icon>
