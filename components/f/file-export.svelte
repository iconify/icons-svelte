<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k10e7hshi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k10e7hshi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-export" {...props}></Icon>
