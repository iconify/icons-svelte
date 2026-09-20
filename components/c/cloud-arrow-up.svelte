<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujwr_lkax.css';
import '../../css/c/c7cgn4zwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujwr_lkax"/><path class="c7cgn4zwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cloud-arrow-up" {...props}></Icon>
