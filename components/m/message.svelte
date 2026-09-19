<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcomewbtu.css';
import '../../css/m/mpg7plbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer pcomewbtu"/><path class="duoicon-primary-layer mpg7plbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:message" {...props}></Icon>
