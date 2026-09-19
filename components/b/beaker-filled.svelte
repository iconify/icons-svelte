<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oip_zgb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oip_zgb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:beaker-filled" {...props}></Icon>
