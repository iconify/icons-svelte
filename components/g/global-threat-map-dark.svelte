<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_0rlkxdi.css';
import '../../css/k/kiwyvcbue.css';
import '../../css/v/vieb4jbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a_0rlkxdi"/><circle class="kiwyvcbue"/><circle class="vieb4jbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:global-threat-map-dark" {...props}></Icon>
