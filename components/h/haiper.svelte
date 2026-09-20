<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8aplcbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t8aplcbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:haiper" {...props}></Icon>
