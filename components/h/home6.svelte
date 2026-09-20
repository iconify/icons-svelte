<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_quhddpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f_quhddpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:home6" {...props}></Icon>
