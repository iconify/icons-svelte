<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7wlg2rof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7wlg2rof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:meteor" {...props}></Icon>
