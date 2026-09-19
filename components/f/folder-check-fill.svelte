<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnmvchc5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vnmvchc5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-check-fill" {...props}></Icon>
