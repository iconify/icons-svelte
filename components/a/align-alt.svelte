<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsk981nza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsk981nza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:align-alt" {...props}></Icon>
