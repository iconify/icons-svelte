<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz_svobux.css';
import '../../css/h/h6ro5gj3z.css';
import '../../css/m/mmux6pkuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wz_svobux"/><path class="h6ro5gj3z"/><path class="mmux6pkuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-forms-dark" {...props}></Icon>
