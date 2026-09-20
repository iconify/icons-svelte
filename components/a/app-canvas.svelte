<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz6mhscer.css';
import '../../css/i/i7nmstb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mz6mhscer ouiIcon__fillSecondary"/><path class="i7nmstb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-canvas" {...props}></Icon>
