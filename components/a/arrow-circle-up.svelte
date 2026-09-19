<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak_owkqcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ak_owkqcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:arrow-circle-up" {...props}></Icon>
