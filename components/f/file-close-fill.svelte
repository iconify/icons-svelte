<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch1todbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ch1todbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:file-close-fill" {...props}></Icon>
