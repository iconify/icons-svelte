<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mia1ztb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mia1ztb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mail-open-heart" {...props}></Icon>
