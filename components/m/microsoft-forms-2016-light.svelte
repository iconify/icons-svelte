<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awo_d-8ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="awo_d-8ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-forms-2016-light" {...props}></Icon>
