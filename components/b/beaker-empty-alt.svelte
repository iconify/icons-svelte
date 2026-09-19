<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaq99ccvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oaq99ccvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:beaker-empty-alt" {...props}></Icon>
