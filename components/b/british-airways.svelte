<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whix8lsva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whix8lsva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:british-airways" {...props}></Icon>
