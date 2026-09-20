<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/taxi_6bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="taxi_6bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:git-repository-line" {...props}></Icon>
