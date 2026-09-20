<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dho1bnojv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dho1bnojv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-38-small" {...props}></Icon>
