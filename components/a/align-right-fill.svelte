<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lajo8c0zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lajo8c0zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-right-fill" {...props}></Icon>
