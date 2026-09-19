<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf87t3b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf87t3b2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:form-location" {...props}></Icon>
