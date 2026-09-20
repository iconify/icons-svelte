<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-w3942xx.css';
import '../../css/c/csowzdbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-w3942xx"/><path class="csowzdbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:fold-up-24" {...props}></Icon>
