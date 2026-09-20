<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx-sycb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tx-sycb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:expand-left" {...props}></Icon>
