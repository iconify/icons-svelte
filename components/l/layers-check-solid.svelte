<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3rw2bc6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3rw2bc6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layers-check-solid" {...props}></Icon>
