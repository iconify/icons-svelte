<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxae0_noe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxae0_noe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:float-center" {...props}></Icon>
