<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg_34mb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg_34mb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-plus-fill" {...props}></Icon>
