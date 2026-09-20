<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gepc7-94s.css';
import '../../css/u/ud-710byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gepc7-94s"/><path class="ud-710byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:microsoft-teams" {...props}></Icon>
