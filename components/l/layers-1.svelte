<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4-v4imeh.css';
import '../../css/m/maj_0caaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="c4-v4imeh"/><path class="maj_0caaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:layers-1" {...props}></Icon>
