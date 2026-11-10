<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhxqnhb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhxqnhb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:folder-check" {...props}></Icon>
