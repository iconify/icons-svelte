<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnk1eyalb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnk1eyalb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pets-at-home" {...props}></Icon>
