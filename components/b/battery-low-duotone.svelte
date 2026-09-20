<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6fzm2b7v.css';
import '../../css/l/luua7ozmy.css';
import '../../css/e/ebj8f9bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="t6fzm2b7v"/><rect class="luua7ozmy"/><rect class="ebj8f9bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:battery-low-duotone" {...props}></Icon>
