<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5_zthcmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="i5_zthcmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:edit" {...props}></Icon>
