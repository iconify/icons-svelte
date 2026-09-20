<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3bf5i-0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3bf5i-0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bracket-arrow-up-sharp" {...props}></Icon>
