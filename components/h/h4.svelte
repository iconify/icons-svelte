<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/virf4bbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="virf4bbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:h4" {...props}></Icon>
