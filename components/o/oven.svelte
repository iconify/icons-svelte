<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw5nfdb1w.css';
import '../../css/a/ap19vnbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw5nfdb1w"/><path class="ap19vnbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:oven" {...props}></Icon>
