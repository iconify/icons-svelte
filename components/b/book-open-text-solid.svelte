<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0qq25bnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0qq25bnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:book-open-text-solid" {...props}></Icon>
