<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jofhjg7gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jofhjg7gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:less" {...props}></Icon>
