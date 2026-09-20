<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aap8i-4xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aap8i-4xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:podcast-outline" {...props}></Icon>
