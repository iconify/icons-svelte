<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnoa_u57u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fnoa_u57u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:number-9-square-solid" {...props}></Icon>
