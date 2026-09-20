<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qefui5bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qefui5bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-progress-three-quarter" {...props}></Icon>
