<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyhf-2_bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyhf-2_bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:question-mark-circle" {...props}></Icon>
