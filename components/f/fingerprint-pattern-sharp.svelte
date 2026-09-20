<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qppqpm--t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qppqpm--t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:fingerprint-pattern-sharp" {...props}></Icon>
