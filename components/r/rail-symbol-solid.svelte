<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_au6tt1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_au6tt1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:rail-symbol-solid" {...props}></Icon>
