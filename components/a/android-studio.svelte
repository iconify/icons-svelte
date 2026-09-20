<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixskfbb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixskfbb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:android-studio" {...props}></Icon>
