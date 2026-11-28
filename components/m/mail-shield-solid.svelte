<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bibvwrb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bibvwrb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mail-shield-solid" {...props}></Icon>
