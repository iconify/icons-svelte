<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_dpj_7ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_dpj_7ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:paperclip" {...props}></Icon>
