<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4p2dtbwt.css';
import '../../css/i/ia-bsrbll.css';
import '../../css/b/bog62tbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4p2dtbwt"/><path class="ia-bsrbll"/><path class="bog62tbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:images" {...props}></Icon>
