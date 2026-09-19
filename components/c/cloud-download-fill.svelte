<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3p3wqb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n3p3wqb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud-download-fill" {...props}></Icon>
