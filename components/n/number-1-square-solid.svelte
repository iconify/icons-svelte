<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmtc7c2_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hmtc7c2_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:number-1-square-solid" {...props}></Icon>
