<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mycr2h52x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mycr2h52x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rocket-alt-filled" {...props}></Icon>
