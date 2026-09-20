<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aygw_60rm.css';
import '../../css/h/h09tvusar.css';
import '../../css/q/qy2alob5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aygw_60rm"/><path class="h09tvusar"/><path clip-rule="evenodd" class="qy2alob5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifer-zoom-out-bold-duotone" {...props}></Icon>
