<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df-3eh3ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="df-3eh3ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:arrow-circle-down" {...props}></Icon>
