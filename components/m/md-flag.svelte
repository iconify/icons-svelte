<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci3qqtbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ci3qqtbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-flag" {...props}></Icon>
