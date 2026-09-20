<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkmpttbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkmpttbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:plr" {...props}></Icon>
