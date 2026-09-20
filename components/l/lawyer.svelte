<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzzn6pbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="bzzn6pbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:lawyer" {...props}></Icon>
