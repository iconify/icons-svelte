<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe_9sqb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qe_9sqb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:buddy" {...props}></Icon>
