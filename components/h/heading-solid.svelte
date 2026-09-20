<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olf_b7bdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olf_b7bdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:heading-solid" {...props}></Icon>
