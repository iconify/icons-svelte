<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af9nr9bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af9nr9bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:charger-1-bold" {...props}></Icon>
