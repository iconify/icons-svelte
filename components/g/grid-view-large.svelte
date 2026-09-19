<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkduf7b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tkduf7b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:grid-view-large" {...props}></Icon>
