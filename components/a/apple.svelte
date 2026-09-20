<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9qv4pbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9qv4pbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:apple" {...props}></Icon>
