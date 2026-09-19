<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc6_2pbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc6_2pbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:locked-env" {...props}></Icon>
