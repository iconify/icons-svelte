<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7juawdew.css';
import '../../css/t/texugffgg.css';
import '../../css/e/euemi1brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p7juawdew"/><path class="texugffgg"/><path class="euemi1brz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:retrofit-20" {...props}></Icon>
