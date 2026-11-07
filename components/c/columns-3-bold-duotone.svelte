<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2-x-cbeh.css';
import '../../css/q/qykqcq_5w.css';
import '../../css/g/gyjvu3nrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2-x-cbeh"/><path class="qykqcq_5w"/><path class="gyjvu3nrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:columns-3-bold-duotone" {...props}></Icon>
