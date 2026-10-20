<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gahgzf5qd.css';
import '../../css/l/l90d81ian.css';
import '../../css/b/bi6je-11k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gahgzf5qd"/><path class="l90d81ian"/><path class="bi6je-11k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bag-plus-20" {...props}></Icon>
