<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pru0h0bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pru0h0bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:laptop" {...props}></Icon>
