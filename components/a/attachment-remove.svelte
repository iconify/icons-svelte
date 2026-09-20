<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amblpqbhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amblpqbhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:attachment-remove" {...props}></Icon>
