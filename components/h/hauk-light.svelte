<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5-noybbr.css';
import '../../css/v/v068-hf6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o5-noybbr"/><path class="v068-hf6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hauk-light" {...props}></Icon>
