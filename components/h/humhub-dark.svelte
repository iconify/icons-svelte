<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edmo9b0vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="edmo9b0vv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:humhub-dark" {...props}></Icon>
