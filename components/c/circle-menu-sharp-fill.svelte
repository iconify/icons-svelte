<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyb81obux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyb81obux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-menu-sharp-fill" {...props}></Icon>
