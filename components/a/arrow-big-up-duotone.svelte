<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duhjdskhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duhjdskhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-up-duotone" {...props}></Icon>
