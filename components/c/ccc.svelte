<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q36idpd-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q36idpd-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ccc" {...props}></Icon>
