<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaz88sxgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kaz88sxgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dacxi" {...props}></Icon>
