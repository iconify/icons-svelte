<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzholcjcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzholcjcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:intermarche" {...props}></Icon>
