<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8a77rbjy.css';
import '../../css/g/gh2npccpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q8a77rbjy"/><path class="gh2npccpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-swap" {...props}></Icon>
