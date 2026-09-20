<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2kb-5rgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2kb-5rgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:loveseat-outline" {...props}></Icon>
