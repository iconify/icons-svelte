<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz_2cui9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mz_2cui9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:beaker-empty-alt-filled" {...props}></Icon>
