<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w42rvhb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w42rvhb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:grid" {...props}></Icon>
