<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw6_glbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yw6_glbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:circle-chevron-up-fill" {...props}></Icon>
