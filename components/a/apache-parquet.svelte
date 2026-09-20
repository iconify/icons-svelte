<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd6no_7gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd6no_7gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apache-parquet" {...props}></Icon>
