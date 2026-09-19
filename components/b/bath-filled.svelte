<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so61k4u2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so61k4u2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bath-filled" {...props}></Icon>
