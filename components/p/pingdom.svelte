<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ano20bb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ano20bb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pingdom" {...props}></Icon>
