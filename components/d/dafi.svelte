<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz66p41ba.css';
import '../../css/x/xdb4trbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hz66p41ba"/><path class="xdb4trbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dafi" {...props}></Icon>
