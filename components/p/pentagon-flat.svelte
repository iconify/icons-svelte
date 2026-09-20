<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy2m-lblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qy2m-lblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:pentagon-flat" {...props}></Icon>
