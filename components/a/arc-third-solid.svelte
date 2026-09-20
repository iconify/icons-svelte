<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjktqzbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjktqzbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arc-third-solid" {...props}></Icon>
