<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5hql90sc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="w5hql90sc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-waning-crescent-6" {...props}></Icon>
