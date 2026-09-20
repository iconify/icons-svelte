<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odnhlrb0v.css';
import '../../css/y/ynooprbfx.css';
import '../../css/i/inbmw3pdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odnhlrb0v"/><path class="ynooprbfx"/><path clip-rule="evenodd" class="inbmw3pdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:calendar-end" {...props}></Icon>
