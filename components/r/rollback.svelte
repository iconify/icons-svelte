<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lby_fq87n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lby_fq87n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:rollback" {...props}></Icon>
