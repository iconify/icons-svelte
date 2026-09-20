<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-k2eg3fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-k2eg3fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:drag-squares-horizontal-light" {...props}></Icon>
