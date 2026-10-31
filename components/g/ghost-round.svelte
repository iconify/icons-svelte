<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke85xxb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke85xxb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ghost-round" {...props}></Icon>
