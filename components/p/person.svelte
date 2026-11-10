<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4yu6jjnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g4yu6jjnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:person" {...props}></Icon>
