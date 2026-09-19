<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqq0l5bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gqq0l5bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:circle-user" {...props}></Icon>
