<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujwr_lkax.css';
import '../../css/h/hntribk9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujwr_lkax"/><path class="hntribk9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cloud-arrow-down" {...props}></Icon>
