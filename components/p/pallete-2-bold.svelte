<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyq-5cc4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dyq-5cc4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pallete-2-bold" {...props}></Icon>
