<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz9xx8brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gz9xx8brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:face-fun" {...props}></Icon>
