<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7gthzjhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7gthzjhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:anyscale" {...props}></Icon>
