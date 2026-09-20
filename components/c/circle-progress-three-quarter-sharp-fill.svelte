<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le_wqjn1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le_wqjn1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-progress-three-quarter-sharp-fill" {...props}></Icon>
