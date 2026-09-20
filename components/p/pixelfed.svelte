<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vybo6ujya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vybo6ujya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pixelfed" {...props}></Icon>
