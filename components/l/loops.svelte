<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oejd0_69w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oejd0_69w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:loops" {...props}></Icon>
