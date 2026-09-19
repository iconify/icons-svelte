<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1w63vikc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l1w63vikc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:opsgenie" {...props}></Icon>
