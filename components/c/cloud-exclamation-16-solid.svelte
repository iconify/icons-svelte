<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3y_oxb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c3y_oxb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cloud-exclamation-16-solid" {...props}></Icon>
