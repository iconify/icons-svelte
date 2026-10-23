<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez92r_4pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ez92r_4pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:dice-5" {...props}></Icon>
