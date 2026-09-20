<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi2o-w3ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi2o-w3ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:empathize-off" {...props}></Icon>
