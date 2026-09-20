<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyyvzf4ru.css';
import '../../css/v/vlxt_3bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyyvzf4ru"/><path class="vlxt_3bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:corner-down-right" {...props}></Icon>
