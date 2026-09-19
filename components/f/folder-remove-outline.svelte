<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wih7av0dv.css';
import '../../css/g/gx2betbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wih7av0dv"/><path class="gx2betbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:folder-remove-outline" {...props}></Icon>
