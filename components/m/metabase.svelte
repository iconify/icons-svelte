<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlrw65cjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlrw65cjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:metabase" {...props}></Icon>
