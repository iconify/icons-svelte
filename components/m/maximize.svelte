<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqofqcupy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqofqcupy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:maximize" {...props}></Icon>
