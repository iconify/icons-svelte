<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqaxcaczw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oqaxcaczw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:framadate-light" {...props}></Icon>
