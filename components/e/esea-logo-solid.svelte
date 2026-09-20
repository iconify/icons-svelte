<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap6yq_jxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ap6yq_jxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:esea-logo-solid" {...props}></Icon>
