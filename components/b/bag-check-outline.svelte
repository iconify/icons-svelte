<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to9jqqqje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="to9jqqqje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-check-outline" {...props}></Icon>
