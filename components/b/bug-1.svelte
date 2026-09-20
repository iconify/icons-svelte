<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0c3qtbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="c0c3qtbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bug-1" {...props}></Icon>
