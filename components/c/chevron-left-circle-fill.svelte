<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8zje8b0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g8zje8b0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:chevron-left-circle-fill" {...props}></Icon>
