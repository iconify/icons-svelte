<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuki3zbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kuki3zbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:film" {...props}></Icon>
