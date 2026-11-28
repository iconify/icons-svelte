<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf8d9fbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf8d9fbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-1-solid" {...props}></Icon>
