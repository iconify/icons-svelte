<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcs0acnmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcs0acnmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-7" {...props}></Icon>
