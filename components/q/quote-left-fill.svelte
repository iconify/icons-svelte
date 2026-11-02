<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsq_ef9ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsq_ef9ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:quote-left-fill" {...props}></Icon>
