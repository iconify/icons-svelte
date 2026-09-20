<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amv03kb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="amv03kb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cassette-outline" {...props}></Icon>
