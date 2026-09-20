<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf5uwnd5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf5uwnd5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:electronics-capacitor-bold" {...props}></Icon>
