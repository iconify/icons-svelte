<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k866ciaux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k866ciaux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-check" {...props}></Icon>
