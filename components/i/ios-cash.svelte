<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_1hnfwlj.css';
import '../../css/m/m50re4ijw.css';
import '../../css/o/okx3-dbox.css';
import '../../css/a/axr2tcbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z_1hnfwlj"/><path class="m50re4ijw"/><path class="okx3-dbox"/><circle class="axr2tcbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cash" {...props}></Icon>
