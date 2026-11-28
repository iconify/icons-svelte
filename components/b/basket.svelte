<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nne51pr0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nne51pr0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:basket" {...props}></Icon>
