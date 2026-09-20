<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnoo_kb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cnoo_kb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-upward-square-fill" {...props}></Icon>
