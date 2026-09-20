<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvs0bnbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvs0bnbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:jfrog" {...props}></Icon>
