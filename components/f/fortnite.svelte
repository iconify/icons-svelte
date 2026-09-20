<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0t-dn8wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0t-dn8wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fortnite" {...props}></Icon>
