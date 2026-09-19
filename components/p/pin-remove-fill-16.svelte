<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egzvq3_2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="egzvq3_2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pin-remove-fill-16" {...props}></Icon>
