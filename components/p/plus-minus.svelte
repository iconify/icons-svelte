<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peuns4bme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="peuns4bme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:plus-minus" {...props}></Icon>
