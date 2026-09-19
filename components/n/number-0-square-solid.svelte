<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozis5k_fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ozis5k_fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:number-0-square-solid" {...props}></Icon>
