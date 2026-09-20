<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpi01cc4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="kpi01cc4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:battery-one-quarter-f" {...props}></Icon>
