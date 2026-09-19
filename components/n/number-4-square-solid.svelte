<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_kod4b-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v_kod4b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:number-4-square-solid" {...props}></Icon>
