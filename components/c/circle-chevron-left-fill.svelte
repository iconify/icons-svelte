<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoz8nebcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hoz8nebcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:circle-chevron-left-fill" {...props}></Icon>
