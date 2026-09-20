<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av5ai0bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av5ai0bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:folder" {...props}></Icon>
