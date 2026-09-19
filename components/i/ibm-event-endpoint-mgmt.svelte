<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs3i02bfn.css';
import '../../css/f/fr-2ovb-v.css';
import '../../css/c/cdqasfbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="cs3i02bfn"/><path class="fr-2ovb-v"/><circle class="cdqasfbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-event-endpoint-mgmt" {...props}></Icon>
