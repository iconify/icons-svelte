<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qccno4t1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qccno4t1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bracket-round" {...props}></Icon>
