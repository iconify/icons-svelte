<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkhynhqrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkhynhqrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:dashboard" {...props}></Icon>
