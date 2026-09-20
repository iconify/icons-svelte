<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwb0a3hgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwb0a3hgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:n26" {...props}></Icon>
