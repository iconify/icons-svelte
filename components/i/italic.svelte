<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zavzltd4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-7.5,"top":-7};
const content = `<path class="zavzltd4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:italic" {...props}></Icon>
