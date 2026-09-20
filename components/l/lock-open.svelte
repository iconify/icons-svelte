<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jku2qqbnp.css';
import '../../css/i/i7sr6ubzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jku2qqbnp"/><path class="i7sr6ubzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:lock-open" {...props}></Icon>
