<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukxrwc2bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukxrwc2bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:number-outline" {...props}></Icon>
