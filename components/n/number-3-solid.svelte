<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqu3ykbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqu3ykbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-3-solid" {...props}></Icon>
