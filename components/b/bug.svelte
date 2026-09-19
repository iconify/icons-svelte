<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1t6bcc2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1t6bcc2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:bug" {...props}></Icon>
