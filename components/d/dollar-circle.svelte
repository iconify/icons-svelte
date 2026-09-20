<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3aun037f.css';
import '../../css/m/mt-ippa9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="e3aun037f"/><path clip-rule="evenodd" class="mt-ippa9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:dollar-circle" {...props}></Icon>
