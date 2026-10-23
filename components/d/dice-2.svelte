<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_l_i2b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_l_i2b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:dice-2" {...props}></Icon>
