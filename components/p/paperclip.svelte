<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iayn1llfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iayn1llfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:paperclip" {...props}></Icon>
