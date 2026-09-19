<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/ml3vkx56u.css';
import '../../css/d/dc2c0qyzp.css';
import '../../css/w/w83s4xb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ml3vkx56u"/><path class="dc2c0qyzp"/><path class="w83s4xb3u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-shared-01" {...props}></Icon>
