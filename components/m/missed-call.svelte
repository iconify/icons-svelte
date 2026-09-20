<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gojrobtkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gojrobtkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:missed-call" {...props}></Icon>
