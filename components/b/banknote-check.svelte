<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0o3itbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0o3itbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:banknote-check" {...props}></Icon>
