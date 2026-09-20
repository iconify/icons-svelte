<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pacdrv3tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pacdrv3tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:process" {...props}></Icon>
