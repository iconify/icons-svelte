<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1-idl2gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1-idl2gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:activity" {...props}></Icon>
