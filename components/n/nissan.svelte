<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3ojj-bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3ojj-bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nissan" {...props}></Icon>
