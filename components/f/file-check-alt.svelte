<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngtfjbbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngtfjbbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-check-alt" {...props}></Icon>
