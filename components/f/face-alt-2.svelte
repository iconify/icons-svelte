<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qilianfni.css';
import '../../css/f/f92imi9ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qilianfni"/><path class="f92imi9ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:face-alt-2" {...props}></Icon>
