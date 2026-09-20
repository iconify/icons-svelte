<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m49f24b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m49f24b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:adobe-alt" {...props}></Icon>
