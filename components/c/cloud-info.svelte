<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl34nzb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl34nzb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cloud-info" {...props}></Icon>
