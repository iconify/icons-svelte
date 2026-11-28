<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jga97rkuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jga97rkuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:italic" {...props}></Icon>
