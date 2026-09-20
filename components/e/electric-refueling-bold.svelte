<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgyhhdc3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mgyhhdc3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:electric-refueling-bold" {...props}></Icon>
