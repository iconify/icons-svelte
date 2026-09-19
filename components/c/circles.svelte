<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gko6svbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gko6svbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circles" {...props}></Icon>
