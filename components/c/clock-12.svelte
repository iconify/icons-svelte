<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7_ncvrna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7_ncvrna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:clock-12" {...props}></Icon>
