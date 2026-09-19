<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcb8w2bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vcb8w2bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-back" {...props}></Icon>
