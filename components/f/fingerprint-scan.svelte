<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-y8l3b9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-y8l3b9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:fingerprint-scan" {...props}></Icon>
