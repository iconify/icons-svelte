<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trilp1bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trilp1bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:folder-arrow-path" {...props}></Icon>
