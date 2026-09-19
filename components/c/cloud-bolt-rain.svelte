<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5cyknb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="a5cyknb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-bolt-rain" {...props}></Icon>
