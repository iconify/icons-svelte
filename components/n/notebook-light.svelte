<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aukfd-bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aukfd-bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:notebook-light" {...props}></Icon>
