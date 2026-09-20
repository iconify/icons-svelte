<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofek2lbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofek2lbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:heart-share" {...props}></Icon>
