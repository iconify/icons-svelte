<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsuy7qb9u.css';
import '../../css/i/if0ri8-so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gsuy7qb9u"/><path class="if0ri8-so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:flexbicep" {...props}></Icon>
