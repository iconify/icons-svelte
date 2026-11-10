<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr1ax_9rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gr1ax_9rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bookmark-plus-solid" {...props}></Icon>
