<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yocctqbef.css';
import '../../css/r/renkk5ypo.css';
import '../../css/y/yepqybc2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yocctqbef"/><path class="renkk5ypo"/><path class="yepqybc2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coffee-machine-20-bold" {...props}></Icon>
