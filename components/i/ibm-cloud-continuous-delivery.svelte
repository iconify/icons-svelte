<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw038zbvw.css';
import '../../css/n/nr8b-db0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tw038zbvw"/><path class="nr8b-db0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-continuous-delivery" {...props}></Icon>
