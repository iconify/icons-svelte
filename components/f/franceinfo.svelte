<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu65d0bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pu65d0bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:franceinfo" {...props}></Icon>
