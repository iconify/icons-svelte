<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_f7928jv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_f7928jv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:floppy-disk" {...props}></Icon>
