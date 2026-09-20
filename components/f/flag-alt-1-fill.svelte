<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2irib6yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2irib6yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flag-alt-1-fill" {...props}></Icon>
