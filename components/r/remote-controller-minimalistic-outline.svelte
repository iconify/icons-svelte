<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj69a5hdy.css';
import '../../css/o/ohpicmbmt.css';
import '../../css/m/mf9o9n5rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gj69a5hdy"/><path class="ohpicmbmt"/><path class="mf9o9n5rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:remote-controller-minimalistic-outline" {...props}></Icon>
