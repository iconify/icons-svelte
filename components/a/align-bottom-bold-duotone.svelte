<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1-qbmafx.css';
import '../../css/u/ul-233bzy.css';
import '../../css/d/dbfay--fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1-qbmafx"/><path class="ul-233bzy"/><path clip-rule="evenodd" class="dbfay--fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-bottom-bold-duotone" {...props}></Icon>
