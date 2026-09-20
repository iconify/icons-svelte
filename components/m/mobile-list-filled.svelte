<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odw3a5f3a.css';
import '../../css/l/l8u2h9byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odw3a5f3a"/><path class="l8u2h9byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mobile-list-filled" {...props}></Icon>
