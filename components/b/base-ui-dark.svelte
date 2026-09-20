<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idh17h92l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":24};
const content = `<path class="idh17h92l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:base-ui-dark" {...props}></Icon>
