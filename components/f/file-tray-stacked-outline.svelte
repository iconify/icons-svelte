<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mud3cttoi.css';
import '../../css/s/szy9kghqd.css';
import '../../css/f/favr_3e4j.css';
import '../../css/h/hfjw3s3ul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mud3cttoi"/><path class="szy9kghqd"/><path class="favr_3e4j"/><path class="hfjw3s3ul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:file-tray-stacked-outline" {...props}></Icon>
