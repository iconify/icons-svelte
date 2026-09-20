<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihcuxaciq.css';
import '../../css/k/k7b4y2y0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ihcuxaciq"/><path class="k7b4y2y0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:espocrm" {...props}></Icon>
