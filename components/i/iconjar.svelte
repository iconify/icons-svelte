<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qex_cbbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qex_cbbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:iconjar" {...props}></Icon>
