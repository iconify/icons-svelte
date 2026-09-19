<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9mei8bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9mei8bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:arrow-right-left" {...props}></Icon>
