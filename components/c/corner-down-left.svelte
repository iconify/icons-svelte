<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1t0m1bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g1t0m1bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:corner-down-left" {...props}></Icon>
