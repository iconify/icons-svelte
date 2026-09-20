<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dix090bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dix090bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:drizzle-fill" {...props}></Icon>
