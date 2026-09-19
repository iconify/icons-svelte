<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyrcwhxhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyrcwhxhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:grok-02" {...props}></Icon>
