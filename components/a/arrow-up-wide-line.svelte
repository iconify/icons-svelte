<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfw__5bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfw__5bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-up-wide-line" {...props}></Icon>
