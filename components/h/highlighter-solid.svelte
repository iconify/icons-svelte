<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyvg2o91f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyvg2o91f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:highlighter-solid" {...props}></Icon>
