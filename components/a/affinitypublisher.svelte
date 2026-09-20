<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-ua1lxok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-ua1lxok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:affinitypublisher" {...props}></Icon>
