<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve86289fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ve86289fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-turn-right-down" {...props}></Icon>
