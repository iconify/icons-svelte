<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afc2go00o.css';
import '../../css/e/edmiowbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="afc2go00o"/><path class="edmiowbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flux-operator-light" {...props}></Icon>
