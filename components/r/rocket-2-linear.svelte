<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls-cjjsgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls-cjjsgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rocket-2-linear" {...props}></Icon>
