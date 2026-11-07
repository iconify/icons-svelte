<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvnq9o5sc.css';
import '../../css/t/tfuw8dqxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvnq9o5sc"/><path class="tfuw8dqxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:camera-rotate-bold-duotone" {...props}></Icon>
