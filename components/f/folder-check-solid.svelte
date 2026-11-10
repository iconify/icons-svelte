<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw203e5eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vw203e5eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:folder-check-solid" {...props}></Icon>
