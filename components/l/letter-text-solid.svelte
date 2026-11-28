<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cidw6ibpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cidw6ibpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:letter-text-solid" {...props}></Icon>
