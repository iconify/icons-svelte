<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu-nt_zvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu-nt_zvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:number-3" {...props}></Icon>
