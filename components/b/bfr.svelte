<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqptalbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqptalbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bfr" {...props}></Icon>
