<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqx47qfla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqx47qfla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:orbit" {...props}></Icon>
