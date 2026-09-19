<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsca1gb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wsca1gb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:badge-cc-fill" {...props}></Icon>
