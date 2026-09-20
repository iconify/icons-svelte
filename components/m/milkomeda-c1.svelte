<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzejkebtm.css';
import '../../css/k/kjmdvfbaw.css';
import '../../css/j/jxve6plzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzejkebtm"/><path class="kjmdvfbaw"/><path class="jxve6plzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:milkomeda-c1" {...props}></Icon>
