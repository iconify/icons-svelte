<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj00pl8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nrj00pl8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:add-shield-half" {...props}></Icon>
