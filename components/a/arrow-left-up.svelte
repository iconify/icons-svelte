<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwzloyzep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwzloyzep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:arrow-left-up" {...props}></Icon>
