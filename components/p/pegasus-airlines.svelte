<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcaykuuxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcaykuuxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pegasus-airlines" {...props}></Icon>
