<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adn-au1cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adn-au1cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:rectangle" {...props}></Icon>
