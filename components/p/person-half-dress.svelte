<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1g2ogzoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="y1g2ogzoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:person-half-dress" {...props}></Icon>
