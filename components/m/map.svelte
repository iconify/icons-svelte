<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkcjtgbqv.css';
import '../../css/s/s9b9x4b1t.css';
import '../../css/v/vysl2zzjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkcjtgbqv wm-k"/><path class="s9b9x4b1t wm-a"/><path class="vysl2zzjq wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:map" {...props}></Icon>
