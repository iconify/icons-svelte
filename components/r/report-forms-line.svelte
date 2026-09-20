<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scj5tm7an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scj5tm7an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:report-forms-line" {...props}></Icon>
