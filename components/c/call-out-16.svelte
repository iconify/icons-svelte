<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftupilb-m.css';
import '../../css/l/lgcy8m5fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ftupilb-m"/><path class="lgcy8m5fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:call-out-16" {...props}></Icon>
