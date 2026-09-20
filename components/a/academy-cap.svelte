<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5zh32dep.css';
import '../../css/t/t9ceisb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j5zh32dep"/><path class="t9ceisb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:academy-cap" {...props}></Icon>
