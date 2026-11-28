<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs3m8nkkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs3m8nkkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:dice-6" {...props}></Icon>
