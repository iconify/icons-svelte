<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2nrf10bf.css';
import '../../css/t/tkfn79bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2nrf10bf"/><path class="tkfn79bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-code-bold-duotone" {...props}></Icon>
