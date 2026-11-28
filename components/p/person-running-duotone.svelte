<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aldbqnb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aldbqnb5t primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:person-running-duotone" {...props}></Icon>
