<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwb8jdbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwb8jdbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:asterisk" {...props}></Icon>
