<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktyj-1b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktyj-1b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:long-up-right" {...props}></Icon>
