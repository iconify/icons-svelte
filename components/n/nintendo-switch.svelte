<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woq1ofeof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="woq1ofeof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:nintendo-switch" {...props}></Icon>
