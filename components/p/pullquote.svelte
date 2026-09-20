<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqx_ddk6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="iqx_ddk6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:pullquote" {...props}></Icon>
