<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_gtpf7cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-1.5};
const content = `<path class="r_gtpf7cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:lifebuoy-f" {...props}></Icon>
