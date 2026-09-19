<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg3tn20le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zg3tn20le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:number-6-square-solid" {...props}></Icon>
