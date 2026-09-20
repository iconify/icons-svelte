<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbah3mb6z.css';
import '../../css/x/xsmw2sb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbah3mb6z"/><path class="xsmw2sb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:palace-2-filled" {...props}></Icon>
