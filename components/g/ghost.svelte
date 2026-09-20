<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxaru7c3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxaru7c3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:ghost" {...props}></Icon>
