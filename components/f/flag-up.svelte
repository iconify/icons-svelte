<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5qnn3pkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5qnn3pkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flag-up" {...props}></Icon>
