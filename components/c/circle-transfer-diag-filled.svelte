<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aopfyn13u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aopfyn13u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-transfer-diag-filled" {...props}></Icon>
