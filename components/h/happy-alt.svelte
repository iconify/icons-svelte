<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu7ist9uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bu7ist9uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:happy-alt" {...props}></Icon>
