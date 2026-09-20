<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw6pfwb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kw6pfwb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:diploma-verified-outline" {...props}></Icon>
