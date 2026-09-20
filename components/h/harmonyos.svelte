<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pasf08bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pasf08bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:harmonyos" {...props}></Icon>
