<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xatnruabq.css';
import '../../css/y/ynuha5bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xatnruabq"/><path class="ynuha5bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:configuration-file" {...props}></Icon>
