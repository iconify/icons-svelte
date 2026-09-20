<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb6jeccxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb6jeccxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-cancel" {...props}></Icon>
