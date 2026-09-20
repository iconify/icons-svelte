<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7no_ob9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7no_ob9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:monoprix" {...props}></Icon>
