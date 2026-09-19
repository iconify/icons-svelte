<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvpf93m0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="vvpf93m0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-arrow-up-right-arrow-down-left-slash" {...props}></Icon>
