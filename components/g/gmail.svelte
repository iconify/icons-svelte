<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fve0jkbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fve0jkbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:gmail" {...props}></Icon>
