<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4b6x6f9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4b6x6f9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fifa" {...props}></Icon>
