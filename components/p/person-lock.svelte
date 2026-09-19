<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvq6t5a9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qvq6t5a9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:person-lock" {...props}></Icon>
