<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihwg2nacl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihwg2nacl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:checklist-boxes" {...props}></Icon>
