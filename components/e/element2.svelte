<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uluni3nio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uluni3nio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:element2" {...props}></Icon>
