<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak0n-9bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ak0n-9bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-left-circle-outline" {...props}></Icon>
