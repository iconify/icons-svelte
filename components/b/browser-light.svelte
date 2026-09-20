<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc21hcbgh.css';
import '../../css/o/o5x0bvbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc21hcbgh"/><path clip-rule="evenodd" class="o5x0bvbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:browser-light" {...props}></Icon>
