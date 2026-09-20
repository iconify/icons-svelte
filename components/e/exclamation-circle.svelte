<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dedb2pwrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dedb2pwrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:exclamation-circle" {...props}></Icon>
