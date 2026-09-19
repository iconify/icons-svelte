<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuu7943dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cuu7943dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:paper-plane-fill" {...props}></Icon>
