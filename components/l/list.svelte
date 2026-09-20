<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imvef3bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imvef3bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:list" {...props}></Icon>
