<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8ckc_bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-5.5};
const content = `<path class="i8ckc_bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:id-card-f" {...props}></Icon>
