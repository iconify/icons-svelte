<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa8p-hbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa8p-hbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:car-wash" {...props}></Icon>
