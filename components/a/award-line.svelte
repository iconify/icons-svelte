<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq6no00vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jq6no00vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:award-line" {...props}></Icon>
