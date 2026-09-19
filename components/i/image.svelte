<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9cmwo62a.css';
import '../../css/s/si1_fnblv.css';
import '../../css/h/hxfqr2z6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="v9cmwo62a"/><path class="si1_fnblv"/><path class="hxfqr2z6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:image" {...props}></Icon>
