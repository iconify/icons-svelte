<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypg3n3bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ypg3n3bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:number-fill-12" {...props}></Icon>
