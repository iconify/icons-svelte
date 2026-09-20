<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-yovpx2o.css';
import '../../css/y/ywduolbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-yovpx2o"/><path class="ywduolbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:diff-modified-24" {...props}></Icon>
