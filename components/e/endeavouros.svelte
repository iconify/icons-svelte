<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/badhlib5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="badhlib5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:endeavouros" {...props}></Icon>
