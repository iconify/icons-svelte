<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdx8udbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdx8udbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:diaspora" {...props}></Icon>
