<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma1a4lbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ma1a4lbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:picartodottv" {...props}></Icon>
