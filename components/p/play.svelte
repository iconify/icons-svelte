<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6dd4tpwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="v6dd4tpwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:play" {...props}></Icon>
