<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9eqnt9qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s9eqnt9qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:closet-outline" {...props}></Icon>
