<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umu-ixchk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umu-ixchk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-1-small" {...props}></Icon>
