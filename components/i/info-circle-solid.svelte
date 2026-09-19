<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hksam20rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hksam20rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:info-circle-solid" {...props}></Icon>
