<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkk9n5bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkk9n5bpf primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:phone-off-duotone" {...props}></Icon>
