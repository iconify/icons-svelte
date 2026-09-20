<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_7m0i8by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_7m0i8by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:almalinux" {...props}></Icon>
