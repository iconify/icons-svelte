<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwtm-ib9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwtm-ib9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:angle-right" {...props}></Icon>
