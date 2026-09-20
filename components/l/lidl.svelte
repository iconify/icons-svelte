<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzn1nb-_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzn1nb-_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:lidl" {...props}></Icon>
