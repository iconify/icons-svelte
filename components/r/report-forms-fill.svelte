<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4jkhtbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4jkhtbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:report-forms-fill" {...props}></Icon>
