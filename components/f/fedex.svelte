<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7a3m7bhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q7a3m7bhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:fedex" {...props}></Icon>
