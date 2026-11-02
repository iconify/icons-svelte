<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpdeyibxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpdeyibxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:medium-line" {...props}></Icon>
