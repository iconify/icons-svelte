<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooffe2bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ooffe2bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-s-right" {...props}></Icon>
