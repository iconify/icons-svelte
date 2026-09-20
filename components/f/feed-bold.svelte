<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oehuv9bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oehuv9bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:feed-bold" {...props}></Icon>
