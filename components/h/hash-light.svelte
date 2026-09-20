<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uusisncih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uusisncih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:hash-light" {...props}></Icon>
