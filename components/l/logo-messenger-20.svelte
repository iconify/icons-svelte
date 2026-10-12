<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5ehvrl0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q5ehvrl0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:logo-messenger-20" {...props}></Icon>
