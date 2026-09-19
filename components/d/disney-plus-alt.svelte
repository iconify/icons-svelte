<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t15ldcb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t15ldcb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:disney-plus-alt" {...props}></Icon>
