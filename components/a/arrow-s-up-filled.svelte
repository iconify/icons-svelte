<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxq6ljq2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxq6ljq2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-s-up-filled" {...props}></Icon>
