<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amlzk90ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="amlzk90ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:religious-muslim-11" {...props}></Icon>
