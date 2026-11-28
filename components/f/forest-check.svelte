<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psqqfy03z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psqqfy03z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:forest-check" {...props}></Icon>
