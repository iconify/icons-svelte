<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9dy06llc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v9dy06llc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cargo-crate" {...props}></Icon>
