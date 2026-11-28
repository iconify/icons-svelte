<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2m2r2hpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2m2r2hpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:folder-open-check" {...props}></Icon>
