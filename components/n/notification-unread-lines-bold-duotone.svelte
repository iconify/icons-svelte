<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv4wotbsh.css';
import '../../css/g/g1b-v8rmi.css';
import '../../css/t/tmzilmxfy.css';
import '../../css/s/siai_tb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv4wotbsh"/><path class="g1b-v8rmi"/><path class="tmzilmxfy"/><path class="siai_tb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notification-unread-lines-bold-duotone" {...props}></Icon>
