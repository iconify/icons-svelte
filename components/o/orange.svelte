<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2mpcgb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2mpcgb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:orange" {...props}></Icon>
