<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5c806b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r5c806b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:angular-outline" {...props}></Icon>
