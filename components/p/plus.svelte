<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9ekx63oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9ekx63oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:plus" {...props}></Icon>
