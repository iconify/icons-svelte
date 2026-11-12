<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feh17ircu.css';
import '../../css/v/v6phkq3ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="feh17ircu"/><path class="v6phkq3ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:journiv" {...props}></Icon>
