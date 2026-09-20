<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzfn8os5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzfn8os5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:paddle" {...props}></Icon>
