<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vagd1bbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vagd1bbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:bill-filled" {...props}></Icon>
