<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj97e-e8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mj97e-e8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:anchor" {...props}></Icon>
