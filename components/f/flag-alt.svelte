<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om1e7y6-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="om1e7y6-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:flag-alt" {...props}></Icon>
