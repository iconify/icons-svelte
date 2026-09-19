<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsm7jgz4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="tsm7jgz4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:font-awesome-flag" {...props}></Icon>
