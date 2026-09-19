<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5kekj5qc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5kekj5qc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:briefcase-alt-2" {...props}></Icon>
