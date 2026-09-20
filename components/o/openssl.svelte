<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaqfptbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gaqfptbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:openssl" {...props}></Icon>
