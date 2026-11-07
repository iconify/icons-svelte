<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrvx3rbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nrvx3rbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:fork-knife-solid" {...props}></Icon>
