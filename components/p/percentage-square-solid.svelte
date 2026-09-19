<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kow7hrb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kow7hrb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:percentage-square-solid" {...props}></Icon>
