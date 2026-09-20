<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqcyc1blh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bqcyc1blh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hand-pills" {...props}></Icon>
