<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcuq4bbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcuq4bbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:colors-square-filled" {...props}></Icon>
