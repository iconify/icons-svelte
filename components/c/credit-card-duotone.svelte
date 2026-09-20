<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6k6c5bss.css';
import '../../css/s/sa4jv-b7i.css';
import '../../css/q/qq3vuebmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6k6c5bss"/><circle class="sa4jv-b7i"/><path class="qq3vuebmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:credit-card-duotone" {...props}></Icon>
