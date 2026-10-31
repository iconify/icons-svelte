<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm53y-svw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm53y-svw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flag-fill-round" {...props}></Icon>
