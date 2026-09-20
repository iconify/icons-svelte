<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwv5mcces.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwv5mcces"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:okex" {...props}></Icon>
