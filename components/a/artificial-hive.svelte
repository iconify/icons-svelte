<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hemi351pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hemi351pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:artificial-hive" {...props}></Icon>
