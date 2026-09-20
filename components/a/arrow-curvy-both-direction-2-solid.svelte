<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob3ob_h0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ob3ob_h0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:arrow-curvy-both-direction-2-solid" {...props}></Icon>
