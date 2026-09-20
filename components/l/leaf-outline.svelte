<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c14g8kbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c14g8kbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:leaf-outline" {...props}></Icon>
