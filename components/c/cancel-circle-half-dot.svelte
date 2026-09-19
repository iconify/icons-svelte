<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhax6sbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhax6sbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cancel-circle-half-dot" {...props}></Icon>
