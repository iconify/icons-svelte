<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_jj_0b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v_jj_0b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:line-arrow-rotate-right-1-remix" {...props}></Icon>
