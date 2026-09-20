<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6eo0_b0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6eo0_b0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:paperclip" {...props}></Icon>
