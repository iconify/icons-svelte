<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toh_b0f4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="toh_b0f4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:banknote-fill" {...props}></Icon>
