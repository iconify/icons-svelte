<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po5vicc7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="po5vicc7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:north-east-line" {...props}></Icon>
