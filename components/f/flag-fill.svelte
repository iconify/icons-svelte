<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7sfqwk7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b7sfqwk7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:flag-fill" {...props}></Icon>
