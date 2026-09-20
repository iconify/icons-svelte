<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzl74qb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzl74qb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevrons-up-solid" {...props}></Icon>
