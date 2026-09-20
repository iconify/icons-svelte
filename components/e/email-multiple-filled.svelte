<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjf7pd.css';
import '../../css/a/a0m25c.css';
import '../../css/m/mi5qmx.css';
import '../../css/z/z4421m.css';
import '../../css/z/z-3bwb.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjf7pd"/><path class="a0m25c mi5qmx"/><path class="a0m25c z4421m"/><path class="a0m25c z-3bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:email-multiple-filled" {...props}></Icon>
