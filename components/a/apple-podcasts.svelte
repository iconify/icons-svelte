<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1ya26b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1ya26b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:apple-podcasts" {...props}></Icon>
