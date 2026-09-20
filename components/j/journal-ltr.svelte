<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgxqd4air.css';
import '../../css/z/zczqr0djk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lgxqd4air"/><path class="zczqr0djk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:journal-ltr" {...props}></Icon>
