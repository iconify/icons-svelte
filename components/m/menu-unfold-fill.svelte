<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njusehpec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njusehpec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-unfold-fill" {...props}></Icon>
