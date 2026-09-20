<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsz_kweuc.css';
import '../../css/n/nb3whwxik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gsz_kweuc"/><path class="nb3whwxik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gamepad-button-right-16" {...props}></Icon>
