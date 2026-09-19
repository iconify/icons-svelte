<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efi4ej_dk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efi4ej_dk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:loader-lines-alt" {...props}></Icon>
