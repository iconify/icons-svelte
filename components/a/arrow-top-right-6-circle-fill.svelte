<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0hfgbc0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k0hfgbc0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-right-6-circle-fill" {...props}></Icon>
