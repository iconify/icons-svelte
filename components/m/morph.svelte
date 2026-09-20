<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpzqq1bhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpzqq1bhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:morph" {...props}></Icon>
