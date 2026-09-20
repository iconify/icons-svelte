<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsl_kkb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsl_kkb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:archive-line" {...props}></Icon>
