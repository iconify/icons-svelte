<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sehyrpkys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="sehyrpkys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-delete-2-remove-bold-add-button-buttons-delete" {...props}></Icon>
