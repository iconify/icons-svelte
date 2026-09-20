<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzr2lqb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzr2lqb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:aliexpress" {...props}></Icon>
