<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3b91b08f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3b91b08f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bone-crack-outline" {...props}></Icon>
