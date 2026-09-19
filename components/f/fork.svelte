<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-gro_bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-gro_bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:fork" {...props}></Icon>
