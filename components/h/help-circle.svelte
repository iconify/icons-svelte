<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4bsowqqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4bsowqqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:help-circle" {...props}></Icon>
