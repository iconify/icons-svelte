<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf-1zmb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf-1zmb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:red" {...props}></Icon>
