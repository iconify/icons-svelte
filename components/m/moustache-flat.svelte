<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4ldzj_ei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e4ldzj_ei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:moustache-flat" {...props}></Icon>
