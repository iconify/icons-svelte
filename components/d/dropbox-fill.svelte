<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pipx4ybrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pipx4ybrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:dropbox-fill" {...props}></Icon>
