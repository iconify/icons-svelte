<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sykv9gb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sykv9gb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:envelope-alt" {...props}></Icon>
