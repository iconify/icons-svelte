<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmj801byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jmj801byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:arrow-right" {...props}></Icon>
