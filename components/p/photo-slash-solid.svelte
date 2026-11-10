<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-93zlopl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e-93zlopl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:photo-slash-solid" {...props}></Icon>
