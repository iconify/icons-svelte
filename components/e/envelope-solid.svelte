<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vplm-nswe.css';
import '../../css/o/oplsioe0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":15};
const content = `<path class="vplm-nswe"/><path class="oplsioe0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:envelope-solid" {...props}></Icon>
