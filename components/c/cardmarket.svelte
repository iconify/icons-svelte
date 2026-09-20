<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj_nm5bhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj_nm5bhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cardmarket" {...props}></Icon>
