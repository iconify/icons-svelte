<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtggf5bet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtggf5bet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hold-02" {...props}></Icon>
