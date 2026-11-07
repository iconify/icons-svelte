<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajralqjgp.css';
import '../../css/s/siai_tb_r.css';
import '../../css/p/p1472sozf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajralqjgp"/><path class="siai_tb_r"/><path class="p1472sozf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:inbox-unread-bold-duotone" {...props}></Icon>
