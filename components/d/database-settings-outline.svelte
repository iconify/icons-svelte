<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0pk_lb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0pk_lb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-settings-outline" {...props}></Icon>
