<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2rq36bvg.css';
import '../../css/s/s1qeddblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2rq36bvg"/><path class="s1qeddblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:boolean-on-24" {...props}></Icon>
