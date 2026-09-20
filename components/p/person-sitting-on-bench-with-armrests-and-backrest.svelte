<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on1pytb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="on1pytb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sitting-on-bench-with-armrests-and-backrest" {...props}></Icon>
