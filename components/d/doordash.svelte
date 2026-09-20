<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huhqg5tve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huhqg5tve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:doordash" {...props}></Icon>
