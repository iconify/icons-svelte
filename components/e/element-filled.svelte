<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkwususpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkwususpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:element-filled" {...props}></Icon>
