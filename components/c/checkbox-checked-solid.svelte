<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aisis0a7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aisis0a7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:checkbox-checked-solid" {...props}></Icon>
