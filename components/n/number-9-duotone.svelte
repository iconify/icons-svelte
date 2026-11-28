<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbkck_nrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbkck_nrq primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-9-duotone" {...props}></Icon>
