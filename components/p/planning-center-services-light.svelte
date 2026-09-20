<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eog45o2id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eog45o2id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-services-light" {...props}></Icon>
