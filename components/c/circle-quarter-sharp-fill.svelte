<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhs2-lbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vhs2-lbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-quarter-sharp-fill" {...props}></Icon>
