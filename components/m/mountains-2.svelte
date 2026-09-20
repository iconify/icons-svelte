<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brno_ib1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="brno_ib1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:mountains-2" {...props}></Icon>
