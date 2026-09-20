<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c84acoxgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c84acoxgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:phone-volume" {...props}></Icon>
