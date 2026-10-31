<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0zh4nbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a0zh4nbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:checklist-solid" {...props}></Icon>
