<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deoxenb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="deoxenb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-0-solid" {...props}></Icon>
