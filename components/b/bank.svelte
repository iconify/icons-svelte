<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivanhnbdc.css';
import '../../css/q/q-befwo0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivanhnbdc"/><path class="q-befwo0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bank" {...props}></Icon>
