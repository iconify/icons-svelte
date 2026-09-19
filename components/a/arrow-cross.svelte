<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cag813bfc.css';
import '../../css/g/givljsy1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cag813bfc"/><path class="givljsy1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-cross" {...props}></Icon>
