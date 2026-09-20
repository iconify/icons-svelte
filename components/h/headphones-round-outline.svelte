<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsv7j_bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tsv7j_bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:headphones-round-outline" {...props}></Icon>
