<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/powm5n7aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="powm5n7aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:play-solid" {...props}></Icon>
