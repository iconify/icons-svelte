<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4kggwbad.css';
import '../../css/u/uek9cd0sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="n4kggwbad"/><path clip-rule="evenodd" class="uek9cd0sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pagination-alt-solid" {...props}></Icon>
