<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q31r1jbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q31r1jbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ferrari" {...props}></Icon>
