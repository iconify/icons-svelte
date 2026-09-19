<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht9r1ybyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ht9r1ybyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:hive" {...props}></Icon>
