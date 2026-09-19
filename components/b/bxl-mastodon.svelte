<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss6w1acng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss6w1acng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-mastodon" {...props}></Icon>
