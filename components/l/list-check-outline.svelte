<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_cz6xddp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_cz6xddp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-check-outline" {...props}></Icon>
