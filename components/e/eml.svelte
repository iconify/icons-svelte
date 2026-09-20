<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt-xd3bpd.css';
import '../../css/y/ynyfbdo0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qt-xd3bpd"/><path class="ynyfbdo0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:eml" {...props}></Icon>
