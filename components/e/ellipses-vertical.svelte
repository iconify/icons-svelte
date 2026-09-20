<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8i4ibc7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8i4ibc7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:ellipses-vertical" {...props}></Icon>
