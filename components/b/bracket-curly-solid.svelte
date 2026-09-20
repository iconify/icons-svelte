<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0g2z9f8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0g2z9f8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bracket-curly-solid" {...props}></Icon>
