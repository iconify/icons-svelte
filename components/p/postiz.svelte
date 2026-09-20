<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6mte0bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6mte0bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:postiz" {...props}></Icon>
