<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j43ytubal.css';
import '../../css/z/zzs5uk6nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j43ytubal"/><path clip-rule="evenodd" class="zzs5uk6nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:open-recent-16" {...props}></Icon>
