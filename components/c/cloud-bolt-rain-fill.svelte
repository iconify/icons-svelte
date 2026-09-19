<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9ui875ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="k9ui875ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-bolt-rain-fill" {...props}></Icon>
