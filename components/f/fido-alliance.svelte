<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btxay1bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btxay1bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fido-alliance" {...props}></Icon>
