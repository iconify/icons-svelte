<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7mf9ilkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7mf9ilkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:formspree" {...props}></Icon>
