<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abe0kqbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="abe0kqbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:reddit-logo-block" {...props}></Icon>
