<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kti7wod0f.css';
import '../../css/b/b2126bb3z.css';
import '../../css/p/pet3n157a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kti7wod0f"/><path class="b2126bb3z"/><path class="pet3n157a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:iot" {...props}></Icon>
