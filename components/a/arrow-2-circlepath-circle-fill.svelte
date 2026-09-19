<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnlimkbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tnlimkbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-2-circlepath-circle-fill" {...props}></Icon>
