<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujwr_lkax.css';
import '../../css/q/qsfwvlb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujwr_lkax"/><path class="qsfwvlb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cloud-arrow-down-duotone" {...props}></Icon>
